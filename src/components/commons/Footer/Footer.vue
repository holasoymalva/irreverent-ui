<template>
  <div class="footer">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';

@Options({
  props: {
    msg: String
  }
})
export default class Footer extends Vue {
  msg!: string
}
</script>
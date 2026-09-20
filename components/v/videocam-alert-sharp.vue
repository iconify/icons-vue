<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzubxabcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:videocam-alert-sharp" /></template>
<style>
.rzubxabcq {
  fill: currentColor;
  d: path("M11.752 19q.356-.683.546-1.429t.19-1.519q0-2.67-1.873-4.543Q8.74 9.634 6.07 9.634q-.69 0-1.337.15q-.648.149-1.253.441V5h14v6.27l3.038-3.04v7.54l-3.038-3.04V19zm-8.587-.164Q2 17.67 2 16t1.165-2.835T6 12t2.836 1.165T10 16t-1.164 2.836T6 20t-2.835-1.164m2.45-2.259h.77v-3h-.77zM6 18.423q.2 0 .33-.13t.132-.332t-.131-.33T6 17.5t-.33.13t-.132.332t.131.33t.331.131");
}

</style>

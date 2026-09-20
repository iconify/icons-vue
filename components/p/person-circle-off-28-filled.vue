<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ktmjzrbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-circle-off-28-filled" /></template>
<style>
.ktmjzrbsr {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l22.5 22.5a.75.75 0 0 1-1.06 1.06l-2.784-2.784A11.95 11.95 0 0 1 14 26C7.373 26 2 20.627 2 14c0-3.044 1.134-5.822 3.002-7.937L2.22 3.28a.75.75 0 0 1 0-1.06M10.143 14C8.959 14 8 14.96 8 16.143c0 3.214 2.686 5.357 6 5.357c1.855 0 3.51-.674 4.61-1.83L12.94 14zM14 2c6.627 0 12 5.373 12 12c0 2.501-.767 4.823-2.076 6.745l-3.962-3.962q.037-.312.038-.64C20 14.959 19.04 14 17.857 14h-.678l-1.805-1.805a3.25 3.25 0 1 0-4.32-4.32l-3.8-3.8A11.94 11.94 0 0 1 14 2");
}

</style>

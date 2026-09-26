<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol_ue80zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:thumbs-up" /></template>
<style>
.ol_ue80zy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 10L8 10L9.6213 3.5149C9.8439 2.6246 10.6438 2 11.5616 2L13.2344 2C14.2431 2 15.0939 2.7511 15.219 3.7519L16 10L20 10C21.1046 10 22 10.8954 22 12C22 12.2398 21.9569 12.4777 21.8727 12.7022L18.8727 20.7022C18.5799 21.4829 17.8337 22 17 22L4 22C2.8954 22 2 21.1046 2 20L2 12C2 10.8954 2.8954 10 4 10ZM8 10L8 22");
}

</style>

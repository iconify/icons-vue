<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tu0bidb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:preview-outline-sharp" /></template>
<style>
.tu0bidb6p {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V7H5zm4.068-3.834Q7.763 14.333 7.096 13q.667-1.333 1.972-2.166Q10.373 10 12 10t2.932.834T16.904 13q-.667 1.333-1.972 2.166Q13.627 16 12 16t-2.932-.834m5.146-.607q1.024-.557 1.732-1.559q-.708-1.002-1.733-1.559T12 10.885t-2.214.556T8.055 13q.707 1.002 1.732 1.559t2.214.557t2.214-.557m-1.42-.766q.322-.322.322-.793t-.323-.793t-.793-.322t-.793.322t-.323.793t.323.793t.793.323t.793-.323");
}

</style>

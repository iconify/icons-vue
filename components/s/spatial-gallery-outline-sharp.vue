<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztqyy5bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:spatial-gallery-outline-sharp" /></template>
<style>
.ztqyy5bqo {
  fill: currentColor;
  d: path("M9.673 16.337h4.654V12.5H9.673zm0-4.837h4.654V7.727H9.673zM4 11.5h4.673V7.71L4 6.323zm0 6.183l4.673-1.293V12.5H4zm16 0V12.5h-4.673v3.89zM15.327 11.5H20V6.423l-4.673 1.204zM3 19V5l6.096 1.75h5.789L21 5.106V19l-6.116-1.664H9.116z");
}

</style>

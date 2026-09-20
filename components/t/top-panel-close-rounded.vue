<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghkpujjew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:top-panel-close-rounded" /></template>
<style>
.ghkpujjew {
  fill: currentColor;
  d: path("m11.435 12.97l-1.927 1.926q-.196.196-.095.448t.383.252h4.406q.275 0 .38-.252t-.09-.449l-1.932-1.931q-.237-.237-.56-.237t-.565.242M5.615 20q-.666 0-1.14-.475T4 18.386V5.615q0-.666.475-1.14T5.615 4h12.77q.666 0 1.14.475T20 5.615v12.77q0 .666-.475 1.14t-1.14.475zM5 9v9.385q0 .23.192.423t.423.192h12.77q.23 0 .423-.192t.192-.423V9z");
}

</style>

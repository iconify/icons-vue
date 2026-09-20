<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm03oybxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:video-frame-save-outline-sharp" /></template>
<style>
.hm03oybxc {
  fill: currentColor;
  d: path("M20 10V6h-4V5h5v5zM3 10V5h5v1H4v4zm0 9v-5h1v4h4v1zm7-3.423V8.423L15.577 12zm5.77 7.917v-1h7v1zm3.5-2.725l-3.308-3.307l.707-.708l2.1 2.088v-4.88h1v4.88l2.1-2.088l.708.707z");
}

</style>

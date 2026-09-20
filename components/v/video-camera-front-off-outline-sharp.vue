<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtuq0gbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-camera-front-off-outline-sharp" /></template>
<style>
.jtuq0gbgu {
  fill: currentColor;
  d: path("m22 17.5l-4-4v1.675l-2-2V6H8.825l-2-2H18v6.5l4-4zm-1.45 5.85L.65 3.45l1.4-1.4l19.9 19.9zM4 4l2 2H4v12h12v-2l2 2v2H2V4zm2 12v-.55q0-1.1 1.1-1.775T10 13t2.9.675T14 15.45V16z");
}

</style>

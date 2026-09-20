<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y938j6bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:youtube-video" /></template>
<style>
.y938j6bvj {
  fill: currentColor;
  d: path("M12.008 18q-1.648 0-3.083-.043q-1.227-.043-2.42-.118t-1.747-.206q-.494-.133-.855-.495q-.36-.361-.497-.838q-.15-.517-.226-1.256t-.118-1.41Q3.02 12.828 3.02 12t.05-1.613q.031-.673.113-1.413q.083-.74.224-1.255q.136-.477.497-.838t.855-.494q.555-.15 1.747-.22q1.191-.069 2.418-.108q1.434-.04 3.077-.04l.933.003q.933.003 2.158.04q1.226.038 2.43.106q1.204.069 1.74.219q.494.133.855.494t.498.838q.14.516.223 1.255q.082.74.113 1.413Q21 11.17 21 12t-.043 1.634q-.043.671-.118 1.41t-.225 1.256q-.137.477-.498.838q-.36.361-.854.495q-.534.132-1.74.209t-2.43.115t-2.155.04zm-1.912-3.442L14.604 12l-4.508-2.539z");
}

</style>

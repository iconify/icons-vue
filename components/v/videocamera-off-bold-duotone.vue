<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ar0kiqktv.css';
import '../../css/p/pa4fm5akg.css';
import '../../css/y/ybtsdob7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ar0kiqktv"/><path class="pa4fm5akg"/><path class="ybtsdob7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:videocamera-off-bold-duotone" /></template>

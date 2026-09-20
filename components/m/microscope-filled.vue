<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pc8b7jb1x.css';
import '../../css/j/jkqdz_yog.css';
import '../../css/x/xnsh14cen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pc8b7jb1x"/><path class="jkqdz_yog"/><path class="xnsh14cen"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:microscope-filled" /></template>

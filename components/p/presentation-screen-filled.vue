<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x200p5olh.css';
import '../../css/e/em7taqccy.css';
import '../../css/g/gue0_kbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x200p5olh"/><rect class="em7taqccy"/><path class="gue0_kbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:presentation-screen-filled" /></template>

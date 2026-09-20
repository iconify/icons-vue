<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t_d03ssda.css';
import '../../css/l/ltz16o8uo.css';
import '../../css/j/jn8p1cftv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="t_d03ssda"/><path class="ltz16o8uo"/><path class="jn8p1cftv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:webcam-bold-duotone" /></template>

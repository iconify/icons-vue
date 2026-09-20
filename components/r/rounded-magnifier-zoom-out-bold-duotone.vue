<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z4ltf1b1v.css';
import '../../css/t/tt17elx2m.css';
import '../../css/e/em6y05bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z4ltf1b1v"/><path class="tt17elx2m"/><path class="em6y05bsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifier-zoom-out-bold-duotone" /></template>

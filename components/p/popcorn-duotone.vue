<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mq21268yd.css';
import '../../css/s/so6tvsbua.css';
import '../../css/r/r6optbbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mq21268yd"/><path class="so6tvsbua"/><path class="r6optbbbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:popcorn-duotone" /></template>

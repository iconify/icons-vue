<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dcj0avb-b.css';
import '../../css/o/o41m46bsm.css';
import '../../css/m/mlgahkksy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dcj0avb-b"/><path class="o41m46bsm"/><path clip-rule="evenodd" class="mlgahkksy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:speaker-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/ksjxiodpt.css';
import '../../css/g/gughkpbfx.css';
import '../../css/u/u5bqo67kp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ksjxiodpt"/><path class="gughkpbfx"/><path clip-rule="evenodd" class="u5bqo67kp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:maximize-square-minimalistic-outline" /></template>

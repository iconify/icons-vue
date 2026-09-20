<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l18a0ac3j.css';
import '../../css/m/mz10oxp2y.css';
import '../../css/w/w1ucf4bqs.css';
import '../../css/z/zmnbfjhed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l18a0ac3j"/><path class="mz10oxp2y"/><circle class="w1ucf4bqs"/><circle class="zmnbfjhed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:text-tool" /></template>

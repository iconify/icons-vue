<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/e/e1dt95bvo.css';
import '../../css/n/nk-f8ubml.css';
import '../../css/o/omnrth6_m.css';
import '../../css/u/u-himcq2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e1dt95bvo"/><path class="nk-f8ubml"/><path class="omnrth6_m"/><path class="u-himcq2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music-playlist" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3fvoac4j.css';
import '../../css/z/z4quglbdj.css';
import '../../css/f/f6pov65_e.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/i/ie431fb2s.css';
import '../../css/y/y8lg_zh2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="d3fvoac4j"/><path class="z4quglbdj"/><path class="f6pov65_e"/><g class="ij2x_72vy"><path class="ie431fb2s"/><path class="y8lg_zh2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:shield" /></template>

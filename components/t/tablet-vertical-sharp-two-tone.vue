<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/q/qd_1w_bij.css';
import '../../css/p/p735-fm4x.css';
import '../../css/z/z9i4rfbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qd_1w_bij"/><path class="p735-fm4x"/><path class="z9i4rfbjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tablet-vertical-sharp-two-tone" /></template>

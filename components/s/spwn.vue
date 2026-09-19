<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jrnd56o7y.css';
import '../../css/m/mxeyk-kuw.css';
import '../../css/l/lm1vs3fnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><path class="jrnd56o7y"/><path class="mxeyk-kuw"/><path class="lm1vs3fnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:spwn" /></template>

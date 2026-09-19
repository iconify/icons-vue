<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kew7uwb2k.css';
import '../../css/e/eo8q52bph.css';
import '../../css/y/yvf29-bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="kew7uwb2k"/><path class="eo8q52bph"/><path class="yvf29-bfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sunset-duo" /></template>

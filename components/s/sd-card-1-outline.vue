<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h_cp8gbnb.css';
import '../../css/t/t-7xstbgc.css';
import '../../css/t/tmav-mb2k.css';
import '../../css/i/imukq7b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="h_cp8gbnb"/><path clip-rule="evenodd" class="t-7xstbgc"/><path class="tmav-mb2k"/><path clip-rule="evenodd" class="imukq7b6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sd-card-1-outline" /></template>

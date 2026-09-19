<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9h87yb9c.css';
import '../../css/i/igis_k17y.css';
import '../../css/r/rw2f_pddh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="s9h87yb9c"><path clip-rule="evenodd" class="igis_k17y"/><path class="rw2f_pddh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:volume" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/nhuasxwps.css';
import '../../css/f/f0eqsgbfe.css';
import '../../css/m/mtmms9b1f.css';
import '../../css/v/v0oar45xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="nhuasxwps"/><path class="f0eqsgbfe"/><path class="mtmms9b1f"/><path class="v0oar45xh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:map-marker-line-outline" /></template>

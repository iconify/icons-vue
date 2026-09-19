<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-70sba8t.css';
import '../../css/d/d2zbbb4nw.css';
import '../../css/m/mo1pfhmuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="f-70sba8t"/><path clip-rule="evenodd" class="d2zbbb4nw"/><path clip-rule="evenodd" class="mo1pfhmuv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:star-half-1" /></template>

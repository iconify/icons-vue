<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/whkshnk2k.css';
import '../../css/h/hbx1wu4pc.css';
import '../../css/b/b7d5grbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="whkshnk2k"/><path class="hbx1wu4pc"/><path class="b7d5grbrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:search" /></template>

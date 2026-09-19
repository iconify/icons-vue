<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/grmn0ni1j.css';
import '../../css/c/c7my2b2pg.css';
import '../../css/m/mgtat6why.css';
import '../../css/o/ophw_-baa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="grmn0ni1j"/><path class="c7my2b2pg"/><path clip-rule="evenodd" class="mgtat6why"/><path class="ophw_-baa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:scissors" /></template>

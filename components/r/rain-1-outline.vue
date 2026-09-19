<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pnt4g603j.css';
import '../../css/l/llko_jr5u.css';
import '../../css/k/k4xzy-b1d.css';
import '../../css/c/cv-_ylbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pnt4g603j"/><path class="llko_jr5u"/><path class="k4xzy-b1d"/><path class="cv-_ylbeb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:rain-1-outline" /></template>

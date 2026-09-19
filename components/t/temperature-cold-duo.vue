<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/eplcf-iln.css';
import '../../css/e/emdguns3d.css';
import '../../css/o/o-jviabzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="eplcf-iln"/><path class="emdguns3d"/><path class="o-jviabzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:temperature-cold-duo" /></template>

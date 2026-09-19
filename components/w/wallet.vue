<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nmd_ebe6d.css';
import '../../css/f/f01wpx3bc.css';
import '../../css/k/k5sacmbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="nmd_ebe6d"/><path class="f01wpx3bc"/><rect class="k5sacmbeu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:wallet" /></template>

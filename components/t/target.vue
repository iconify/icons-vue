<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jv4k-10ho.css';
import '../../css/p/pnbbm9bfl.css';
import '../../css/u/u819g2d_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="jv4k-10ho"/><path class="pnbbm9bfl"/><path class="u819g2d_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:target" /></template>

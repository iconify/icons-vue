<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n-jost8nj.css';
import '../../css/h/hv4d2qb8d.css';
import '../../css/x/xaqcxbcrv.css';
import '../../css/n/nck8zjbny.css';
import '../../css/r/r89u6hn1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="n-jost8nj"/><path class="hv4d2qb8d"/><rect class="xaqcxbcrv"/><path class="nck8zjbny"/><path class="r89u6hn1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:router" /></template>

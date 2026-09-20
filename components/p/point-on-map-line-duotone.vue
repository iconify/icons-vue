<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/r_kmw_yut.css';
import '../../css/z/zv97pxbdl.css';
import '../../css/p/ptvu1u_4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="r_kmw_yut"/><path class="zv97pxbdl"/><circle class="ptvu1u_4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:point-on-map-line-duotone" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/x_-vy9bff.css';
import '../../css/s/src5g-5zv.css';
import '../../css/p/pbkmeu61n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x_-vy9bff"/><path class="src5g-5zv"/><path class="pbkmeu61n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-rotate-broken" /></template>

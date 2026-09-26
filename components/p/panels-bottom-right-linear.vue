<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i22s-4u1h.css';
import '../../css/t/t1j-_8esg.css';
import '../../css/d/dplnzz0rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i22s-4u1h"/><path class="t1j-_8esg"/><path class="dplnzz0rj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-bottom-right-linear" /></template>

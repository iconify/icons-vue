<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rjomr8bgz.css';
import '../../css/p/p3_4el9va.css';
import '../../css/c/csckydbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rjomr8bgz"/><path class="p3_4el9va"/><path class="csckydbbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-academic-cap-linear" /></template>

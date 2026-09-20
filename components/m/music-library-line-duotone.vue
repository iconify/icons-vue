<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/ea_31gbnm.css';
import '../../css/u/u9_hwpzmi.css';
import '../../css/v/vnsop5_4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ea_31gbnm"/><path class="u9_hwpzmi"/><path class="vnsop5_4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-library-line-duotone" /></template>

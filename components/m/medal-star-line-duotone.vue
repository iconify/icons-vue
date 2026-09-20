<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u5a8z1bvb.css';
import '../../css/t/tu9ed8abb.css';
import '../../css/p/py9khzhop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u5a8z1bvb"/><path class="tu9ed8abb"/><path class="py9khzhop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-star-line-duotone" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i1vfzkb9v.css';
import '../../css/r/rifo2czrt.css';
import '../../css/c/ctgpv1blf.css';
import '../../css/y/y8fghij0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i1vfzkb9v"/><path class="rifo2czrt"/><path class="ctgpv1blf"/><path class="y8fghij0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:palette-line-duotone" /></template>

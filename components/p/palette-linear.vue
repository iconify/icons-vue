<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i1vfzkb9v.css';
import '../../css/e/ehgxs22fz.css';
import '../../css/c/ctgpv1blf.css';
import '../../css/w/w9x56_fne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i1vfzkb9v"/><path class="ehgxs22fz"/><path class="ctgpv1blf"/><path class="w9x56_fne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:palette-linear" /></template>

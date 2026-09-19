<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kz-2l07lp.css';
import '../../css/y/y5xl-gbup.css';
import '../../css/y/y1pnovgss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kz-2l07lp"/><path class="y5xl-gbup"/><path class="y1pnovgss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sofa-single" /></template>

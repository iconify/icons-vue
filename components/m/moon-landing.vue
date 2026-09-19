<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kp4sgbfpe.css';
import '../../css/i/iqamq8bdl.css';
import '../../css/y/y6ovjwbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kp4sgbfpe"/><path class="iqamq8bdl"/><path class="y6ovjwbid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:moon-landing" /></template>

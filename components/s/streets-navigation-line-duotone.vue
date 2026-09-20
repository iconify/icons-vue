<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qgtd8187v.css';
import '../../css/u/u7mrcgb5f.css';
import '../../css/f/fbtujzbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qgtd8187v"/><path class="u7mrcgb5f"/><path class="fbtujzbta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-navigation-line-duotone" /></template>

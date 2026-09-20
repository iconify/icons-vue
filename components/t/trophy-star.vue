<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cpx6cvtmg.css';
import '../../css/k/knuyjfb2y.css';
import '../../css/n/n95nkccdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cpx6cvtmg"/><path class="knuyjfb2y"/><path class="n95nkccdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:trophy-star" /></template>

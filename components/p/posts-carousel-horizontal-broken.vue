<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i96tnwb9m.css';
import '../../css/n/n9n4_cako.css';
import '../../css/o/oi_mcozlx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i96tnwb9m"/><path class="n9n4_cako"/><path class="oi_mcozlx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:posts-carousel-horizontal-broken" /></template>

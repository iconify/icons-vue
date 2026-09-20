<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vq8-hu_1o.css';
import '../../css/b/b581idbbf.css';
import '../../css/o/ozst3gb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vq8-hu_1o"/><path class="b581idbbf"/><circle transform="rotate(-45 8.607 8.879)" class="ozst3gb1r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tag-price-linear" /></template>

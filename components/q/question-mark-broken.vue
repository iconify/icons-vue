<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jbz4_mzqr.css';
import '../../css/t/tyv5mcb3q.css';
import '../../css/n/n6_kje8jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jbz4_mzqr"/><path class="tyv5mcb3q"/><path class="n6_kje8jt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:question-mark-broken" /></template>

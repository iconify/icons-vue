<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njc6web4n.css';
import '../../css/i/iqll_cgam.css';
import '../../css/i/i5ggx7ltg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="njc6web4n"/><path class="iqll_cgam"/><path class="i5ggx7ltg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-bowtie" /></template>

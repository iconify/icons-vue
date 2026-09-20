<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kj9125bhw.css';
import '../../css/u/ubsyz0bji.css';
import '../../css/a/a09g2ehcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kj9125bhw"/><path class="ubsyz0bji"/><path class="a09g2ehcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-graph-line-duotone" /></template>

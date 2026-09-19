<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kyg4webhc.css';
import '../../css/q/q9tflhftz.css';
import '../../css/i/iem8lp2xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kyg4webhc"/><path class="q9tflhftz"/><path class="iem8lp2xo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:package-remove" /></template>

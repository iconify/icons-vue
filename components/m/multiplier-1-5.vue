<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uywc1tb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":24};
const content = `<path class="uywc1tb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:multiplier-1-5" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg0lupbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg0lupbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tradingview" /></template>

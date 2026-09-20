<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt3b0obzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jt3b0obzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tradingview" /></template>

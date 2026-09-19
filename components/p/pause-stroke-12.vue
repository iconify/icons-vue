<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_2-kvb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="f_2-kvb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pause-stroke-12" /></template>

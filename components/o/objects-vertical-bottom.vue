<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2u2kvb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2u2kvb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:objects-vertical-bottom" /></template>

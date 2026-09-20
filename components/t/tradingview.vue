<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv2hi7bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv2hi7bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tradingview" /></template>

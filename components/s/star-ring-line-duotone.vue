<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rachw9boo.css';
import '../../css/i/i3ileybjz.css';
import '../../css/f/fhnye3b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rachw9boo"/><path class="i3ileybjz"/><path class="fhnye3b1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-ring-line-duotone" /></template>

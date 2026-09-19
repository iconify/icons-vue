<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dncd5rb1n.css';
import '../../css/i/iue80nb2y.css';
import '../../css/f/fky6n3bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dncd5rb1n"/><path class="iue80nb2y"/><path class="fky6n3bak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:truck-length" /></template>

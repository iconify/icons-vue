<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/d2fl3m4rd.css';
import '../../css/c/c2lq5wbok.css';
import '../../css/m/mjuiasbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d2fl3m4rd"/><path class="c2lq5wbok"/><path class="mjuiasbra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:package-x" /></template>

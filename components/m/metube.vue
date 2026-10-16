<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uehp1-aij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":500};
const content = `<path class="uehp1-aij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:metube" /></template>

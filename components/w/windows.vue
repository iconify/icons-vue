<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtb0g6klh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mtb0g6klh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:windows" /></template>

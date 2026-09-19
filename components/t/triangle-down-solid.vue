<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwc4woboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vwc4woboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:triangle-down-solid" /></template>

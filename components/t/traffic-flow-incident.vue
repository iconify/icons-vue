<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehaqvxe4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ehaqvxe4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:traffic-flow-incident" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vat4d3csq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vat4d3csq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sailboat-coastal" /></template>

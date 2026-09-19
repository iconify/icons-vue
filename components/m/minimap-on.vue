<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4vs41bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i4vs41bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:minimap-on" /></template>

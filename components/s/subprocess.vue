<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsza6i97b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nsza6i97b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:subprocess" /></template>

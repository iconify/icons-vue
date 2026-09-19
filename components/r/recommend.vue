<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlidzc3gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tlidzc3gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:recommend" /></template>

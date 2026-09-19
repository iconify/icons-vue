<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvhszz85h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yvhszz85h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:manjaro" /></template>

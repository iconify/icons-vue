<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh6vd3p4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yh6vd3p4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ngc" /></template>

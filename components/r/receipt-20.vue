<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pepcxkbtl.css';
import '../../css/m/mvmh7mwai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pepcxkbtl"/><path class="mvmh7mwai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:receipt-20" /></template>

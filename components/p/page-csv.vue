<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8_7k8mch.css';
import '../../css/f/fd4fpfb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="f8_7k8mch"/><path class="fd4fpfb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:page-csv" /></template>

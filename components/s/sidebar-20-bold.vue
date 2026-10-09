<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nivpnqg4j.css';
import '../../css/p/pddr5rgfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nivpnqg4j"/><path class="pddr5rgfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sidebar-20-bold" /></template>

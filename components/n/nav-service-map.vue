<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5cq5vwjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p5cq5vwjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-service-map" /></template>

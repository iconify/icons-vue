<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhrvo3buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rhrvo3buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:vaadin-v" /></template>

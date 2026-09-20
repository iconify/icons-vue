<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1o8eolcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m1o8eolcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-ticketing" /></template>

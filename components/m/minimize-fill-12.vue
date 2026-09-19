<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cos1jybps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="cos1jybps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:minimize-fill-12" /></template>

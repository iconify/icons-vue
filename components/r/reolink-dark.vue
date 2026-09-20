<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy6h1cb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vy6h1cb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reolink-dark" /></template>

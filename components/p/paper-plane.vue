<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx4-b78rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cx4-b78rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:paper-plane" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oat-qbbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oat-qbbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tiktok-dark" /></template>

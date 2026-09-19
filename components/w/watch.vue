<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2x4u1b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":512};
const content = `<path class="l2x4u1b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:watch" /></template>

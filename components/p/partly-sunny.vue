<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx_j7qbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vx_j7qbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:partly-sunny" /></template>

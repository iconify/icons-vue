<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv8_5tben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nv8_5tben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-people" /></template>

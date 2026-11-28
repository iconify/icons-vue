<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w94ft6b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="w94ft6b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:postcard-fill" /></template>

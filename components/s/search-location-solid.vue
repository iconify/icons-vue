<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3y3f8jnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d3y3f8jnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:search-location-solid" /></template>

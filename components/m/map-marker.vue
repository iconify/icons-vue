<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvi3j2b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="uvi3j2b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:map-marker" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6dm7wbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w6dm7wbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:map-center" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppq1nhbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ppq1nhbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:thermometer-three-quarters-solid" /></template>

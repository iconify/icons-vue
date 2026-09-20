<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olt9o2bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="olt9o2bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sliders-h-solid" /></template>

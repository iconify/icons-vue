<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld-4lsb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ld-4lsb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mostly-cloudy" /></template>

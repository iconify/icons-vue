<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-ysc-d4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y-ysc-d4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:traffic-cone" /></template>

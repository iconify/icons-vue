<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5q4pvb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":408};
const content = `<path class="c5q4pvb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:mic-off" /></template>

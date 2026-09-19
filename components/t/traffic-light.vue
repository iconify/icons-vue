<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk8k6mbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="dk8k6mbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:traffic-light" /></template>

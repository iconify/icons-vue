<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar-w1rbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ar-w1rbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:onwatch-light" /></template>

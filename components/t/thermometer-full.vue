<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2u6px6tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q2u6px6tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:thermometer-full" /></template>

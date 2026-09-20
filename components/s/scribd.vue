<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fczfo0zmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fczfo0zmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:scribd" /></template>

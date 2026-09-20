<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxix2hbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qxix2hbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:truck-monster-solid" /></template>

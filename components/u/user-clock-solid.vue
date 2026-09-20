<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi2g_bcsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hi2g_bcsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:user-clock-solid" /></template>

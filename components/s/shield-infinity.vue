<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp6qz_ktz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yp6qz_ktz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:shield-infinity" /></template>

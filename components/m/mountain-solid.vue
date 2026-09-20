<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx4wm_5bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nx4wm_5bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:mountain-solid" /></template>

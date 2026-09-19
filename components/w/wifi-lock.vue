<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh756ubkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":504,"height":408};
const content = `<path class="sh756ubkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:wifi-lock" /></template>

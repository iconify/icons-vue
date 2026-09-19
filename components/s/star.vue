<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta3t5ry5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":408};
const content = `<path class="ta3t5ry5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:star" /></template>

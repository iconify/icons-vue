<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrcm8ibqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="hrcm8ibqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:map-location" /></template>

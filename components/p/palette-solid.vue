<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itj0e37iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="itj0e37iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:palette-solid" /></template>

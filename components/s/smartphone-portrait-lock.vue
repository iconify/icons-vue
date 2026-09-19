<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke6k-nk_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":480};
const content = `<path class="ke6k-nk_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:smartphone-portrait-lock" /></template>

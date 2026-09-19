<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekn05fbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":480};
const content = `<path class="ekn05fbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:smartphone-lock" /></template>

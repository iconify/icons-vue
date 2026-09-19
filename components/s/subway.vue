<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m38t_g0lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":408};
const content = `<path class="m38t_g0lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:subway" /></template>

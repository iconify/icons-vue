<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbjd4bx_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mbjd4bx_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:runkeeper" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz_wyfb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mz_wyfb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:snm" /></template>

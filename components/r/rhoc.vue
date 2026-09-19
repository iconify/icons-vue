<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdu5zac3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hdu5zac3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:rhoc" /></template>

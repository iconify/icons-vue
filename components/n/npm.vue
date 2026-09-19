<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysqt9cbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ysqt9cbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:npm" /></template>

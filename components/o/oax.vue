<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7ri8h3mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s7ri8h3mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:oax" /></template>

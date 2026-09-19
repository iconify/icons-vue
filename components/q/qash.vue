<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea1-t_1gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ea1-t_1gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:qash" /></template>

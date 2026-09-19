<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr-egnj3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sr-egnj3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:req" /></template>

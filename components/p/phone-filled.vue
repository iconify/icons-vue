<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6xnh5bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g6xnh5bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:phone-filled" /></template>

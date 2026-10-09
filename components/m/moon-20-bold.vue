<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1_27vbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z1_27vbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-20-bold" /></template>

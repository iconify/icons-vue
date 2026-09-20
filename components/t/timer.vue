<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee3w8bc4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ee3w8bc4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:timer" /></template>

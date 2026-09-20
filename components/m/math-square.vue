<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3t03_b4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3t03_b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:math-square" /></template>

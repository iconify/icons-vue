<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiha8cybs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tiha8cybs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:silent-line" /></template>

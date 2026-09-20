<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulkqwac8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulkqwac8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mountain-2-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjvf8qbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjvf8qbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:snow-line" /></template>

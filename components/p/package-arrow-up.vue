<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io8g53b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io8g53b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:package-arrow-up" /></template>

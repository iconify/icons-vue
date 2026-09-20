<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgv33zbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgv33zbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:snowstorm-line" /></template>

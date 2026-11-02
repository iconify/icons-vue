<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6ui_zbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6ui_zbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transformation-line" /></template>

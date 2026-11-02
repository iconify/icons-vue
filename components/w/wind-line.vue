<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pibo6ybvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pibo6ybvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wind-line" /></template>

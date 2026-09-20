<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdx9atftz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdx9atftz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tv-1-line" /></template>

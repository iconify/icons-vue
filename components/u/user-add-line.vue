<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8d6p67qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8d6p67qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-add-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usefx23gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="usefx23gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wind-fill" /></template>

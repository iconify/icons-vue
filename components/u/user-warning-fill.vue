<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrbthqxox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrbthqxox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-warning-fill" /></template>

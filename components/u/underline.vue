<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nskt8_var.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nskt8_var"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:underline" /></template>

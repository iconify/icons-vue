<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h68dr0b5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h68dr0b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moon-stars-line" /></template>

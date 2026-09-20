<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi95u7abw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi95u7abw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:steering-wheel-fill" /></template>

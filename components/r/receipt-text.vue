<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7xvwxbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7xvwxbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:receipt-text" /></template>

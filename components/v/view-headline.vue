<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2yf0pbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2yf0pbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-headline" /></template>

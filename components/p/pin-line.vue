<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijwgb3btt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijwgb3btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:pin-line" /></template>

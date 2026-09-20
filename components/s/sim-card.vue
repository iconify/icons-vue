<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od2b1-boe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="od2b1-boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:sim-card" /></template>

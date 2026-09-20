<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0kdu23ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0kdu23ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:server-line" /></template>

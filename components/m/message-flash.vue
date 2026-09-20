<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6s-a99um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6s-a99um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:message-flash" /></template>

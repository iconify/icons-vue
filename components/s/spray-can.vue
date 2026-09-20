<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1cswyb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1cswyb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:spray-can" /></template>

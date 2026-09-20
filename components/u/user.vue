<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnog5tw8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnog5tw8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:user" /></template>

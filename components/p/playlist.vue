<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8n5xcpzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o8n5xcpzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:playlist" /></template>

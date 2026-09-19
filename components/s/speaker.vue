<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvne6vqbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="kvne6vqbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:speaker" /></template>

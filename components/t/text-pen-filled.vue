<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2d3u4bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2d3u4bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:text-pen-filled" /></template>

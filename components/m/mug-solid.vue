<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6x6upbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6x6upbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:mug-solid" /></template>

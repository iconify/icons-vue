<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe0fey4fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe0fey4fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:table" /></template>

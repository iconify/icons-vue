<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwhlflb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wwhlflb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:star-and-crescent" /></template>

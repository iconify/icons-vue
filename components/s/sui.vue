<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk_t99b9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk_t99b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sui" /></template>

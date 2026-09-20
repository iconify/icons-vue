<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo7mvpg8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo7mvpg8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:office-building-cog-outline" /></template>

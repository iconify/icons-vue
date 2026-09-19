<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjzh2jrou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjzh2jrou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:microphone-off" /></template>

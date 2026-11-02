<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk66__azu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk66__azu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pencil-ruler-line" /></template>

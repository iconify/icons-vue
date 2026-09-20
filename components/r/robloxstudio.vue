<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdps-gl2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdps-gl2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:robloxstudio" /></template>

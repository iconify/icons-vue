<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuiwdk09n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuiwdk09n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table" /></template>

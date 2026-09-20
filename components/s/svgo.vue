<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk0s25b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk0s25b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:svgo" /></template>

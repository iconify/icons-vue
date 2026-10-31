<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0mu64ktm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0mu64ktm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:navigation-fill-round" /></template>

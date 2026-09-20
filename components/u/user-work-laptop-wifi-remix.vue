<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4h3mqyon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y4h3mqyon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-work-laptop-wifi-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuok2rbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fuok2rbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:middle-click-remix" /></template>

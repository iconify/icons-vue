<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvkcdmb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvkcdmb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:messages-bubble-square-typing-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/calhe9bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="calhe9bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:power-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n92ifub3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n92ifub3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sword-round" /></template>

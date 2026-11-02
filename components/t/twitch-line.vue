<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uft_mybdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uft_mybdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:twitch-line" /></template>

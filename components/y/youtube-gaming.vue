<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thw8f5_hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thw8f5_hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:youtube-gaming" /></template>

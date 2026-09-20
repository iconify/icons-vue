<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlm5zeidu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlm5zeidu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:social-x-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca9c8-5ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca9c8-5ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:play-large-fill" /></template>

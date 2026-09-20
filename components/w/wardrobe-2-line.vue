<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtesqvhax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtesqvhax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wardrobe-2-line" /></template>

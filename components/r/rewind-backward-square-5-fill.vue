<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgj-9x8dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgj-9x8dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-backward-square-5-fill" /></template>

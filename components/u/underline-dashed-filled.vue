<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_8m3-boe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_8m3-boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:underline-dashed-filled" /></template>

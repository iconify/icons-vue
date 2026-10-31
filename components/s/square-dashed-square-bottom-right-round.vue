<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdqmb4bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdqmb4bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-bottom-right-round" /></template>

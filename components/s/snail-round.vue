<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_wiu9bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_wiu9bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:snail-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8li0ibhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8li0ibhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ship-fill-round" /></template>

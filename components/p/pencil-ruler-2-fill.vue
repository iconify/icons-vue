<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni6nc-c3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni6nc-c3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pencil-ruler-2-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0dbrw-yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y0dbrw-yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tube-lotion-filled" /></template>

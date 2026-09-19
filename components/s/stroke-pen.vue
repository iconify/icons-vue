<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1kxvcc1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1kxvcc1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:stroke-pen" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v320si-go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v320si-go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pen-plus-filled" /></template>

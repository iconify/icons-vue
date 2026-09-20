<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc03b0xex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc03b0xex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:omega" /></template>

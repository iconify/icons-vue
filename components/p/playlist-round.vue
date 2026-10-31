<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeucowb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yeucowb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playlist-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7v2a1bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7v2a1bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:youtube-round" /></template>

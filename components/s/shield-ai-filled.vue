<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntws4y6ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntws4y6ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:shield-ai-filled" /></template>

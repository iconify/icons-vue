<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikp4edbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikp4edbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trending-up-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9wey62wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i9wey62wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ststars" /></template>

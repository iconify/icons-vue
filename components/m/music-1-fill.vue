<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5aw_t51u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d5aw_t51u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:music-1-fill" /></template>

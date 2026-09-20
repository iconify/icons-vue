<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8zl8jb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8zl8jb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:newspaper-variant" /></template>

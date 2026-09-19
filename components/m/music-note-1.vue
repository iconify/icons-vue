<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgfrnkb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgfrnkb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:music-note-1" /></template>

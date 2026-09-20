<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5ua0i-bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5ua0i-bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:movie-edit-outline" /></template>

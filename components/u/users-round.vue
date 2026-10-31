<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suw5ydbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suw5ydbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:users-round" /></template>

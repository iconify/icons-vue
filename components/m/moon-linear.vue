<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjc34rbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjc34rbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:moon-linear" /></template>

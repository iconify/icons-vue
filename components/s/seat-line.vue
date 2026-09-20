<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvq4241xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvq4241xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:seat-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcxy16pkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcxy16pkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:scissors" /></template>

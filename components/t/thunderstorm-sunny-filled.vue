<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-svsnkck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-svsnkck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:thunderstorm-sunny-filled" /></template>

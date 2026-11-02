<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb5c5ou6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb5c5ou6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:video-camera-2-fill" /></template>

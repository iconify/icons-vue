<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m40pek_uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m40pek_uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:video-camera-2-fill" /></template>

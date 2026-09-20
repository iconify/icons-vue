<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r07pqrkez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r07pqrkez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:youtube-gaming-logo-1-solid" /></template>

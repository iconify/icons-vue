<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mky3ybctq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mky3ybctq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:youtube-music-logo-solid" /></template>

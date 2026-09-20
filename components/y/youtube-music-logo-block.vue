<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u__5w_y6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u__5w_y6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:youtube-music-logo-block" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u624y-kis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u624y-kis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:youtube-gaming-logo-2-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxmr4jb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxmr4jb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-switch-outline" /></template>

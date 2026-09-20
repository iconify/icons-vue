<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulfynybjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulfynybjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:terminal-box-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiv79zbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uiv79zbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:twitch-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwo41-b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwo41-b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:twitter-logo-1" /></template>

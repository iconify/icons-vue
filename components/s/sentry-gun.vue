<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh36zabkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wh36zabkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sentry-gun" /></template>

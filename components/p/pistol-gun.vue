<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-i5cov4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q-i5cov4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pistol-gun" /></template>

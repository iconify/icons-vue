<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpjtu2prx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wpjtu2prx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sprout-disc" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6w2__w5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i6w2__w5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-in-steamy-room" /></template>

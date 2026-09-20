<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isqzje__y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="isqzje__y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:music-assistant-dark" /></template>

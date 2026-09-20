<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu8nvy21f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gu8nvy21f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:windows-retro-dark" /></template>

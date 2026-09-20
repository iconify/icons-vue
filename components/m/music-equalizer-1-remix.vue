<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syraodb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="syraodb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:music-equalizer-1-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp4sxebmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fp4sxebmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-emoji-terrified-remix" /></template>

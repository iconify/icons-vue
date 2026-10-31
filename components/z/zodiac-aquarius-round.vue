<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z22p2s54p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z22p2s54p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-aquarius-round" /></template>

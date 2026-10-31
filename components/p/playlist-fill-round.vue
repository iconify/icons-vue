<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kukuwbwmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kukuwbwmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playlist-fill-round" /></template>

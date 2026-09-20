<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiuggabrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kiuggabrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:squidoo-logo-block" /></template>

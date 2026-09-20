<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iegig96lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iegig96lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:zodiac-gemini" /></template>

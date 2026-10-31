<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp11kbk4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp11kbk4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-sparkle-fill-round" /></template>

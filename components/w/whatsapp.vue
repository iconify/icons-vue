<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1dkykb1h.css';
import '../../css/m/mtoynvb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1dkykb1h"/><path class="mtoynvb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:whatsapp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if9nj_b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if9nj_b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square-chevron-right" /></template>

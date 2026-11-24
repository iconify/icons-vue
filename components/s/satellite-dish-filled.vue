<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv62zlbwh.css';
import '../../css/r/rpzzz8b2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv62zlbwh"/><path class="rpzzz8b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:satellite-dish-filled" /></template>

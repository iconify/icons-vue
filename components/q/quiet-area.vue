<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fue3z8bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fue3z8bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:quiet-area" /></template>

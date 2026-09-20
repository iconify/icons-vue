<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilt0r1bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilt0r1bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:size-xl" /></template>

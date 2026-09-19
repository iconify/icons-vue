<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eryjosv9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eryjosv9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sword-03" /></template>

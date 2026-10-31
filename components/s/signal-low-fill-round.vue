<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1hufhbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1hufhbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signal-low-fill-round" /></template>

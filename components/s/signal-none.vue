<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1ewhsb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="i1ewhsb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:signal-none" /></template>

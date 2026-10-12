<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb_pv7qoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb_pv7qoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pencil-sparkles-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0yu7z-4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0yu7z-4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-align-justify-bulk-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7cz4mnsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7cz4mnsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-face-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t96m9ac6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t96m9ac6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:speech-to-text-line" /></template>

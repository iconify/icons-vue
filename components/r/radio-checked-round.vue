<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2_bmgbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2_bmgbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radio-checked-round" /></template>

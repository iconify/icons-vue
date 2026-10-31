<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbmm16d-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbmm16d-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:underline-round" /></template>

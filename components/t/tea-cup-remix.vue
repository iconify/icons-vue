<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgmm_puok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zgmm_puok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tea-cup-remix" /></template>

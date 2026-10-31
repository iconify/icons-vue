<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiprb2byv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uiprb2byv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pill-round" /></template>

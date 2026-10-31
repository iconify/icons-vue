<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlli4dbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlli4dbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-bottom-round" /></template>

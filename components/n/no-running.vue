<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwvlvdbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwvlvdbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-running" /></template>

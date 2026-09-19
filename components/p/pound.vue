<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zotwl3b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zotwl3b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:pound" /></template>

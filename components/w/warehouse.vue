<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws2q6wr8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ws2q6wr8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:warehouse" /></template>

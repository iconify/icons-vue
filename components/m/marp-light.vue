<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g22qdwbvx.css';
import '../../css/j/jahsuebty.css';
import '../../css/d/dcbk0ez8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g22qdwbvx"/><path class="jahsuebty"/><path class="dcbk0ez8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:marp-light" /></template>

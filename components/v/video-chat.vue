<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz517qe8i.css';
import '../../css/t/tmstyeo8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mz517qe8i"/><path class="tmstyeo8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:video-chat" /></template>

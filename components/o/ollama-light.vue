<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufa1labba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ufa1labba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ollama-light" /></template>

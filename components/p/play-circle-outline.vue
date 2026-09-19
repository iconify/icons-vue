<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwlmahb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="cwlmahb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:play-circle-outline" /></template>

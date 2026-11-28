<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7e0f9b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="s7e0f9b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:music-notes-slash" /></template>

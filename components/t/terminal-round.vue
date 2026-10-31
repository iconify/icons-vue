<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y64kgqkua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y64kgqkua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:terminal-round" /></template>

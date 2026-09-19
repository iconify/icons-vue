<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egjdr5bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="egjdr5bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:terminal-window-stroke-12" /></template>

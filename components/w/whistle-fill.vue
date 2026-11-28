<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln38mfb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ln38mfb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:whistle-fill" /></template>

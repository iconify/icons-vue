<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb1eob28e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":500};
const content = `<path clip-rule="evenodd" class="hb1eob28e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:roblox" /></template>

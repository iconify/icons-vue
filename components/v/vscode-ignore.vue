<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc801-15m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hc801-15m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:vscode-ignore" /></template>

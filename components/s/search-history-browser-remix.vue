<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc3vo21sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pc3vo21sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:search-history-browser-remix" /></template>

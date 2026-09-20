<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gev4v268m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gev4v268m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:module-puzzle-2-remix" /></template>

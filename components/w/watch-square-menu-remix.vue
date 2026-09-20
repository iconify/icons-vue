<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s93-4-ktg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s93-4-ktg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:watch-square-menu-remix" /></template>

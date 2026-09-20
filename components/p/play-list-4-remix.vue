<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6nv8rb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y6nv8rb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:play-list-4-remix" /></template>

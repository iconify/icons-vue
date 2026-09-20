<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3d0_1qju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i3d0_1qju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:new-folder-remix" /></template>

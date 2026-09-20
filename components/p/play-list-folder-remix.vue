<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd6hbhzah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vd6hbhzah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:play-list-folder-remix" /></template>

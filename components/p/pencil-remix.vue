<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3caf4h6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w3caf4h6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pencil-remix" /></template>

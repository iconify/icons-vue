<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erl6f0bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="erl6f0bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pyramid-shape-remix" /></template>

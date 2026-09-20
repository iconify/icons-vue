<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy3rupbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cy3rupbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:select-circle-area-1-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5_n65d2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j5_n65d2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:threat-folder-remix" /></template>

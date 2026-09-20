<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfrrrab-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rfrrrab-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:straight-face-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjt6f0b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hjt6f0b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pi-symbol-circle-remix" /></template>

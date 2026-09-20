<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f118krgzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f118krgzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:peace-hand-remix" /></template>

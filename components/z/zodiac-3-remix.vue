<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7ryd22fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e7ryd22fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:zodiac-3-remix" /></template>

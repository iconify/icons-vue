<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkmcn9brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bkmcn9brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tablet-capsule-remix" /></template>

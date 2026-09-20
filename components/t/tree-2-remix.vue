<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsih90_mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gsih90_mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tree-2-remix" /></template>

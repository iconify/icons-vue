<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq9se5byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uq9se5byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:strategy-tasks-remix" /></template>

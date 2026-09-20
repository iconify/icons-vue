<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0kg0ccbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v0kg0ccbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:subtract-square-remix" /></template>

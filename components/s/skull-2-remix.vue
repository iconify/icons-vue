<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot8g6wbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ot8g6wbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:skull-2-remix" /></template>

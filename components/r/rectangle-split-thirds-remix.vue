<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o90uxgbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o90uxgbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:rectangle-split-thirds-remix" /></template>

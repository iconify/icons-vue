<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev4xohbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ev4xohbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:toilet-man-remix" /></template>

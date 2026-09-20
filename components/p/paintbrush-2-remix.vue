<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uugljcccz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uugljcccz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:paintbrush-2-remix" /></template>

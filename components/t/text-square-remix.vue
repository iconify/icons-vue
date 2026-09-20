<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1b_g1bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s1b_g1bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:text-square-remix" /></template>

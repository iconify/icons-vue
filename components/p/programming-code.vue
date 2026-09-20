<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0_0luk2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i0_0luk2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:programming-code" /></template>

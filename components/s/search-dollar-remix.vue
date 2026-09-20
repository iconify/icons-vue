<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f041-1cwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f041-1cwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:search-dollar-remix" /></template>

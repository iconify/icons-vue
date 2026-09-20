<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7q77thdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j7q77thdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mail-search-remix" /></template>

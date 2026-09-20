<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3srjgb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c3srjgb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:rotate-angle-45-solid" /></template>

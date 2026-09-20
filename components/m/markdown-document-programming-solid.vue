<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4dbs1bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u4dbs1bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:markdown-document-programming-solid" /></template>

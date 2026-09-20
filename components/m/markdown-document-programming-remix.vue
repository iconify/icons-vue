<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4awffbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b4awffbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:markdown-document-programming-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jspn7gvku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jspn7gvku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:markdown-circle-programming-remix" /></template>

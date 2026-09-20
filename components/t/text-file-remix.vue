<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwd09ej6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kwd09ej6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:text-file-remix" /></template>

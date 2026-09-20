<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9c-hf5ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a9c-hf5ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:shirt-remix" /></template>

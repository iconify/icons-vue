<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apz8k-boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="apz8k-boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:rocket-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_tevem9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q_tevem9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:padlock-square-1-remix" /></template>

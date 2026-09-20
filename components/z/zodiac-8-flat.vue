<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1t6ehbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s1t6ehbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:zodiac-8-flat" /></template>

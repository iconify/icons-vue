<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alqrtaccc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="alqrtaccc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:zodiac-6-flat" /></template>

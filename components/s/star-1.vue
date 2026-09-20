<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5-y5lyfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="q5-y5lyfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:star-1" /></template>

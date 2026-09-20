<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l201mbccu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="l201mbccu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:subtract-1" /></template>

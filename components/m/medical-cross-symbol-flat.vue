<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klb9dw5dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="klb9dw5dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:medical-cross-symbol-flat" /></template>

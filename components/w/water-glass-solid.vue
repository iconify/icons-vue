<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl1cs6bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zl1cs6bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:water-glass-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn18cu8da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cn18cu8da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:module-puzzle-2-solid" /></template>

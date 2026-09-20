<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcr4y4byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lcr4y4byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pool-ladder-solid" /></template>

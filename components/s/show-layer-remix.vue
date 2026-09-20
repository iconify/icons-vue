<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzq55c3ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lzq55c3ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:show-layer-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgtb5dhkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dgtb5dhkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:table-remix" /></template>

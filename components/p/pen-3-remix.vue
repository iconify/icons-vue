<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhdha2bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vhdha2bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pen-3-remix" /></template>

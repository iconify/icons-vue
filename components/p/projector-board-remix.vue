<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbzmhxo-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rbzmhxo-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:projector-board-remix" /></template>

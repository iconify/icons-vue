<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjq8q_b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mjq8q_b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:pen-tool-remix" /></template>

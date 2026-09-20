<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw56xxatz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="aw56xxatz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:stairs-1-remix" /></template>

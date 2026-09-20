<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg-68ml4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gg-68ml4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:store-2-remix" /></template>

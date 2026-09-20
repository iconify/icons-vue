<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-qdyxf9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x-qdyxf9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:phone-remix" /></template>

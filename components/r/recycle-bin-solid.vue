<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmbbn3sob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nmbbn3sob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:recycle-bin-solid" /></template>

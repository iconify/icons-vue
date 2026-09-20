<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nglbulbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nglbulbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:polaroid-four-solid" /></template>

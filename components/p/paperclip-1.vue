<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg_s6ibdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cg_s6ibdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:paperclip-1" /></template>

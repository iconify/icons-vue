<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pykmghbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="pykmghbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:paperclip-1" /></template>

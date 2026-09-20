<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjgmjeb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tjgmjeb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:shovel-rake-flat" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqmd109zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eqmd109zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:new-folder-flat" /></template>

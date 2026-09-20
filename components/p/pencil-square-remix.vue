<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr-h59kjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mr-h59kjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:pencil-square-remix" /></template>

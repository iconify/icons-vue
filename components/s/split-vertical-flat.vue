<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmdvb9gaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rmdvb9gaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:split-vertical-flat" /></template>

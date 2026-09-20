<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi7xitnqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yi7xitnqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:satellite-dish-solid" /></template>

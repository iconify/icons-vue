<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3t-g3ebi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y3t-g3ebi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:screen-curve-solid" /></template>

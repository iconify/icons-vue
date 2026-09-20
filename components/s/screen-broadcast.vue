<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2797jbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="c2797jbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:screen-broadcast" /></template>

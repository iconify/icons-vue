<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0t6jfbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h0t6jfbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:webcam-remix" /></template>

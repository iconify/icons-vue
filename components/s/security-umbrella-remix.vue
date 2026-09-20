<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyheiuxlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yyheiuxlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:security-umbrella-remix" /></template>

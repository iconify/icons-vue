<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1hf5acsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="v1hf5acsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:wifi-horizontal" /></template>

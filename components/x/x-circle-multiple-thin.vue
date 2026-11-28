<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qix83dbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qix83dbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:x-circle-multiple-thin" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9usotbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g9usotbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:square" /></template>

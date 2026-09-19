<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkcugybwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jkcugybwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:network-2" /></template>

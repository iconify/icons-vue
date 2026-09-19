<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eero-xijc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="eero-xijc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:mars-and-venus-burst" /></template>

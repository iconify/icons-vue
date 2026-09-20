<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-nn87blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="z-nn87blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:slash" /></template>

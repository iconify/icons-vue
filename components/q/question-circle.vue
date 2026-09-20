<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zt0gceb0n.css';
import '../../css/o/o3oqjvb4j.css';
import '../../css/x/x-_389brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(2 2)" class="bi12bsetm"><circle class="zt0gceb0n"/><path class="o3oqjvb4j"/><circle class="x-_389brr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:question-circle" /></template>

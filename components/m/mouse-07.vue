<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/ocr4r30uq.css';
import '../../css/c/c1t6ucbve.css';
import '../../css/o/oae0thbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ocr4r30uq"/><path class="c1t6ucbve"/><path class="oae0thbyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mouse-07" /></template>

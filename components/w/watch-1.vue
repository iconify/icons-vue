<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z4rbfsbwr.css';
import '../../css/l/lil4qobow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="z4rbfsbwr"/><path class="lil4qobow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:watch-1" /></template>

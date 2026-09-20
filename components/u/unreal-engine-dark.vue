<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx5d-bc1s.css';
import '../../css/t/tv92lqy5r.css';
import '../../css/f/f4v228b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g clip-rule="evenodd" class="nx5d-bc1s"><path class="tv92lqy5r"/><path class="f4v228b-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:unreal-engine-dark" /></template>

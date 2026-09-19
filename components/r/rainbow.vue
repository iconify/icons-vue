<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pwhf0db-z.css';
import '../../css/d/d18ycsb5v.css';
import '../../css/w/wov5-s89s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="pwhf0db-z"/><path class="d18ycsb5v"/><path class="wov5-s89s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:rainbow" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yg-e9wbuc.css';
import '../../css/p/ptezgqtbz.css';
import '../../css/n/nazz6ccrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="yg-e9wbuc"/><path class="ptezgqtbz"/><path class="nazz6ccrh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sign-railroad-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/z02wksbvu.css';
import '../../css/o/o1l3xfb8l.css';
import '../../css/j/j0ba43ftm.css';
import '../../css/v/vgrxbcbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="z02wksbvu"/><path class="o1l3xfb8l"/><path class="j0ba43ftm"/><rect class="vgrxbcbxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:seal" /></template>

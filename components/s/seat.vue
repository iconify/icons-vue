<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/l/lrqwqdbew.css';
import '../../css/p/pd5_1mzss.css';
import '../../css/g/gnkx5hbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="lrqwqdbew"/><path class="pd5_1mzss"/><circle class="gnkx5hbtb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:seat" /></template>

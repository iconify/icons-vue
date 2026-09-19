<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/j64jqwfra.css';
import '../../css/z/zgv3likpx.css';
import '../../css/b/bxtnlct1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="j64jqwfra"/><path class="zgv3likpx"/><path class="bxtnlct1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:woman" /></template>

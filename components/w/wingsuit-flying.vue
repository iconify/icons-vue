<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btx30rb9t.css';
import '../../css/i/i_r28w9ux.css';
import '../../css/y/ydkw8wkxd.css';
import '../../css/c/crqsvlbwz.css';
import '../../css/v/v2j7te83t.css';
import '../../css/c/cylzn3m1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="btx30rb9t"><path class="i_r28w9ux"/><path class="ydkw8wkxd"/><path class="crqsvlbwz"/><path class="v2j7te83t"/><path class="cylzn3m1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:wingsuit-flying" /></template>

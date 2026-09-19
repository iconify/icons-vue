<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/u/uvh5rrbvb.css';
import '../../css/c/cqdgwh-af.css';
import '../../css/s/sjya5bbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="uvh5rrbvb"/><path class="cqdgwh-af"/><path class="sjya5bbyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:mouse-one" /></template>

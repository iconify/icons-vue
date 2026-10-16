<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdclrrbld.css';
import '../../css/z/zrqa_4kry.css';
import '../../css/j/j0szhnrrq.css';
import '../../css/d/dlcn8obnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kdclrrbld"/><path class="zrqa_4kry"/><path class="j0szhnrrq"/><path class="dlcn8obnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:soil-carbon-48-bold" /></template>

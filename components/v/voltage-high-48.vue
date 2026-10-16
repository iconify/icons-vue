<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqoqidbfs.css';
import '../../css/o/oa5v05bkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jqoqidbfs"/><path class="oa5v05bkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltage-high-48" /></template>

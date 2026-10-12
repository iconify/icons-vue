<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf93xsbmn.css';
import '../../css/k/kjf3iqboc.css';
import '../../css/f/fmo52ol9d.css';
import '../../css/t/t2smvv9rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pf93xsbmn"/><path class="kjf3iqboc"/><path class="fmo52ol9d"/><path class="t2smvv9rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pushpin-48" /></template>

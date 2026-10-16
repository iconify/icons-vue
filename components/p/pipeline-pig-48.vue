<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgga-fb4g.css';
import '../../css/s/sw35zxvtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jgga-fb4g"/><path class="sw35zxvtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipeline-pig-48" /></template>

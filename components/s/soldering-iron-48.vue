<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awek-epgl.css';
import '../../css/b/brfai6b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="awek-epgl"/><path class="brfai6b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:soldering-iron-48" /></template>

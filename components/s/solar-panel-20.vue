<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt1fwi76j.css';
import '../../css/b/bfm65zb3s.css';
import '../../css/m/m4sog_j7e.css';
import '../../css/f/fp_b-wf4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rt1fwi76j"/><path class="bfm65zb3s"/><path class="m4sog_j7e"/><path class="fp_b-wf4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-panel-20" /></template>

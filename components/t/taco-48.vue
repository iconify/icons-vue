<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqn9w_jlc.css';
import '../../css/e/e2_8yl1ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dqn9w_jlc"/><path class="e2_8yl1ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:taco-48" /></template>

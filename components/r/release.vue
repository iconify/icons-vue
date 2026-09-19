<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqfvh-g1q.css';
import '../../css/d/dappoac4j.css';
import '../../css/x/xsnosccfg.css';
import '../../css/p/pmjjzy17v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dqfvh-g1q"/><path class="dappoac4j"/><path class="xsnosccfg"/><path class="pmjjzy17v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:release" /></template>

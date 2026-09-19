<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkfottbas.css';
import '../../css/c/c3z6yg-qu.css';
import '../../css/w/w2k4c4jrl.css';
import '../../css/j/j40lfpbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kkfottbas"/><path class="c3z6yg-qu"/><path class="w2k4c4jrl"/><path class="j40lfpbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:org" /></template>

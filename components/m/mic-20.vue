<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_3g6zbib.css';
import '../../css/n/nin37acqn.css';
import '../../css/y/y6gb_wbfk.css';
import '../../css/y/yrp93bbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e_3g6zbib"/><path class="nin37acqn"/><path class="y6gb_wbfk"/><path class="yrp93bbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mic-20" /></template>

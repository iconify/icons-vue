<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8zkctbrn.css';
import '../../css/b/bru00mf_u.css';
import '../../css/o/o2czk5b_p.css';
import '../../css/j/j14ip5bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":230};
const content = `<path class="i8zkctbrn"/><path class="bru00mf_u"/><path class="o2czk5b_p"/><path class="j14ip5bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:react-query" /></template>

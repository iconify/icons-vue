<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/j_xescbfb.css';
import '../../css/a/a3h_uub7j.css';
import '../../css/n/nnb345baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="j_xescbfb"/><path class="a3h_uub7j"/><path class="nnb345baj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:query-pagination-numbers" /></template>

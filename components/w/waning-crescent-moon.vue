<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-o_jbbvn.css';
import '../../css/u/u50yvab1y.css';
import '../../css/i/i7fzjucdq.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/u/usozxnbrm.css';
import '../../css/a/awrvu0bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="h-o_jbbvn"/><circle class="u50yvab1y"/><path class="i7fzjucdq"/><g class="jn8qy4bru"><circle class="usozxnbrm"/><path class="awrvu0bnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:waning-crescent-moon" /></template>

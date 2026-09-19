<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/c974-jgxw.css';
import '../../css/h/hi4pc4bnr.css';
import '../../css/v/v15isc0yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><path class="c974-jgxw"/><circle class="hi4pc4bnr"/><circle class="v15isc0yr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:skull" /></template>

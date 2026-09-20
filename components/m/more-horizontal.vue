<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/jxl67pbry.css';
import '../../css/r/r2l1z561j.css';
import '../../css/s/s5qf56fne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="jxl67pbry"/><circle class="r2l1z561j"/><circle class="s5qf56fne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:more-horizontal" /></template>

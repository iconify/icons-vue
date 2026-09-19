<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/p4pwxrbiv.css';
import '../../css/s/snp4gwbyg.css';
import '../../css/c/c7q11z5lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p4pwxrbiv"/><path class="snp4gwbyg"/><circle class="c7q11z5lw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:pen-tool" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/y/y2rj0nmor.css';
import '../../css/z/zv6cqnbnp.css';
import '../../css/e/ez1x61b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y2rj0nmor"/><circle class="zv6cqnbnp"/><circle class="ez1x61b2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:map-pin-search" /></template>

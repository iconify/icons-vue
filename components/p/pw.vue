<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lj1b5bc8e.css';
import '../../css/p/pr7jl7ryw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":301,"height":189};
const content = `<g class="ft5dv1b6b"><path class="lj1b5bc8e"/><circle class="pr7jl7ryw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:pw" /></template>

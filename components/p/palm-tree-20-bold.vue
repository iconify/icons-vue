<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqbdr3bwf.css';
import '../../css/l/lq302uv1z.css';
import '../../css/g/gsxsmjbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dqbdr3bwf"/><path class="lq302uv1z"/><path class="gsxsmjbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:palm-tree-20-bold" /></template>

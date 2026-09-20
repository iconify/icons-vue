<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/l6a6v_m7k.css';
import '../../css/j/j0kx2gbuw.css';
import '../../css/i/i71k519nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="l6a6v_m7k"/><path class="j0kx2gbuw"/><path class="i71k519nu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:paginate-filter-music" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cjqq4fblg.css';
import '../../css/j/jeqtdlb7k.css';
import '../../css/y/yplpaeb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cjqq4fblg"/><path class="jeqtdlb7k"/><path class="yplpaeb1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:search-x-duotone" /></template>

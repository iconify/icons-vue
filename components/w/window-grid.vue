<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g18t66qmd.css';
import '../../css/l/lf_du3q8d.css';
import '../../css/j/jcogv-28d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g18t66qmd"/><path class="lf_du3q8d"/><path class="jcogv-28d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:window-grid" /></template>

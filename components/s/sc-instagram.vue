<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/a/ag4ld1ntb.css';
import '../../css/t/tmhwtbj8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="n1lsf0bnc"><path class="ag4ld1ntb"/><path class="tmhwtbj8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:sc-instagram" /></template>

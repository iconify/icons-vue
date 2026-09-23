<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbozhdcpj.css';
import '../../css/s/sb-7x_b3r.css';
import '../../css/f/fzmbfkb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":120,"height":120};
const content = `<g class="zbozhdcpj"><circle class="sb-7x_b3r"/><path class="fzmbfkb6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nodebo" /></template>

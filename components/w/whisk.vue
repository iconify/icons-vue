<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/axxphcgys.css';
import '../../css/m/ma-1r2bqx.css';
import '../../css/e/evxn836au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="axxphcgys"/><path class="ma-1r2bqx"/><path class="evxn836au"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:whisk" /></template>

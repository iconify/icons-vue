<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_2lkqbxb.css';
import '../../css/m/m-24ijb3r.css';
import '../../css/d/dbu_26btw.css';
import '../../css/b/bsg406b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="m-24ijb3r"/><path class="dbu_26btw"/><path class="bsg406b6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:npm-lock" /></template>

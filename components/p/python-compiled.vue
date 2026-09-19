<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_2lkqbxb.css';
import '../../css/q/q2cbt3b-c.css';
import '../../css/x/x_er3gb5y.css';
import '../../css/g/gsr5-p44z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="q2cbt3b-c"/><path class="x_er3gb5y"/><path class="gsr5-p44z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:python-compiled" /></template>

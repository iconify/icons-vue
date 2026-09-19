<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/i/istz93bkq.css';
import '../../css/d/d1nyn72ly.css';
import '../../css/y/ylzxxojfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="istz93bkq"/><path class="d1nyn72ly"/><path class="ylzxxojfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:neutral-face-bold" /></template>

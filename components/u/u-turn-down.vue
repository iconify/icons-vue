<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/x/x6nhvj-7w.css';
import '../../css/x/xupb65btz.css';
import '../../css/y/y525ptbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="x6nhvj-7w"/><path class="xupb65btz"/><circle transform="rotate(90 35 39)" class="y525ptbor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:u-turn-down" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/b/b_0d5acja.css';
import '../../css/c/cnglzpbpe.css';
import '../../css/f/fezbgdcig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="b_0d5acja"/><path class="cnglzpbpe"/><circle class="fezbgdcig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:rotate-one" /></template>

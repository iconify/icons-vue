<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvklctb1s.css';
import '../../css/h/hck-_bb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xvklctb1s"/><path class="hck-_bb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:pie-graph" /></template>

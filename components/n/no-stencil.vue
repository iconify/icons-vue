<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvsu9ljnl.css';
import '../../css/w/whpncgbes.css';
import '../../css/l/lr0wsqbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zvsu9ljnl"/><path class="whpncgbes"/><path class="lr0wsqbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:no-stencil" /></template>

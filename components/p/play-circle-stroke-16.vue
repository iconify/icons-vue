<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upo67d98k.css';
import '../../css/i/ikh678xfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<circle class="upo67d98k"/><path class="ikh678xfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:play-circle-stroke-16" /></template>

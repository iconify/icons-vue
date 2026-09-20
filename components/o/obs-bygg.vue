<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jywu-rbdx.css';
import '../../css/h/hppnn5bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jywu-rbdx"/><path class="hppnn5bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:obs-bygg" /></template>

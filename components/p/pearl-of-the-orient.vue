<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/q/q53134oub.css';
import '../../css/m/m9awzuz4m.css';
import '../../css/i/izz9u2a6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="q53134oub"/><circle class="m9awzuz4m"/><path class="izz9u2a6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:pearl-of-the-orient" /></template>

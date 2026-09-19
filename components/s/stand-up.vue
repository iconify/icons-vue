<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/a/axkk8gb6r.css';
import '../../css/m/m19n9hzdc.css';
import '../../css/a/a9rdrsqxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="axkk8gb6r"/><path class="m19n9hzdc"/><circle class="a9rdrsqxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:stand-up" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zen2agbyu.css';
import '../../css/h/hb4ovmb-c.css';
import '../../css/r/rbbtambdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zen2agbyu"/><path class="hb4ovmb-c"/><path class="rbbtambdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:steering-wheel-48" /></template>

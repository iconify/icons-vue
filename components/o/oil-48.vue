<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4lu07s0y.css';
import '../../css/l/l_8wx2fdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r4lu07s0y"/><path class="l_8wx2fdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oil-48" /></template>

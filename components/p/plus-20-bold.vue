<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swevlxb4e.css';
import '../../css/h/hgy1l_tlx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="swevlxb4e"/><path class="hgy1l_tlx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plus-20-bold" /></template>

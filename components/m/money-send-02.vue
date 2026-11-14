<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/pgjt86b_x.css';
import '../../css/u/ukm46zb4e.css';
import '../../css/b/bxwgwkbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pgjt86b_x"/><path class="ukm46zb4e"/><path class="bxwgwkbpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:money-send-02" /></template>

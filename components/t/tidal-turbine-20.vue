<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbbf18bwz.css';
import '../../css/b/b_eke94bd.css';
import '../../css/p/p415zm30i.css';
import '../../css/p/pt38gvb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rbbf18bwz"/><path class="b_eke94bd"/><path class="p415zm30i"/><path class="pt38gvb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tidal-turbine-20" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bt__3t6bm.css';
import '../../css/j/j9gaom6_i.css';
import '../../css/c/cnc8kxp4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bt__3t6bm"/><circle class="j9gaom6_i"/><circle class="cnc8kxp4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tangent" /></template>

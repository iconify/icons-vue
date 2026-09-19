<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/je98fibcj.css';
import '../../css/p/p3wftabhp.css';
import '../../css/k/kt_vqgb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="je98fibcj"/><path class="p3wftabhp"/><path class="kt_vqgb8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rainbow" /></template>

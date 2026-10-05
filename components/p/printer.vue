<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/s/s4uk_ibbx.css';
import '../../css/v/vu2z3zbex.css';
import '../../css/d/dm-ajb7yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="s4uk_ibbx"/><path class="vu2z3zbex"/><path class="dm-ajb7yk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:printer" /></template>

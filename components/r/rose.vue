<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lxqkkqmys.css';
import '../../css/t/td49gbbjb.css';
import '../../css/j/j314kuthn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lxqkkqmys"/><path class="td49gbbjb"/><path class="j314kuthn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rose" /></template>

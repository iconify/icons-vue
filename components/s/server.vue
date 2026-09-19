<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/wheiic_ie.css';
import '../../css/t/t_a38r7nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><rect class="wheiic_ie"/><line x1="2.25" x2="13.75" y1="8.25" y2="8.25"/><path class="t_a38r7nw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:server" /></template>

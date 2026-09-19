<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/j_sh1-wma.css';
import '../../css/y/y15c62b3m.css';
import '../../css/z/ztt3ox3cd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="j_sh1-wma"/><path class="y15c62b3m"/><path class="ztt3ox3cd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:stationery" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/k--uqqbpr.css';
import '../../css/l/leiq1ib6u.css';
import '../../css/h/hc2a3kmhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="k--uqqbpr"/><circle class="leiq1ib6u"/><circle class="hc2a3kmhy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:plate" /></template>

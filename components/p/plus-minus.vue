<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/m_n3hfvmo.css';
import '../../css/v/vx6s_6z_m.css';
import '../../css/l/l9asld1on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="m_n3hfvmo"/><path class="vx6s_6z_m"/><path class="l9asld1on"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:plus-minus" /></template>

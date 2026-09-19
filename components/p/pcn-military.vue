<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q693w62tt.css';
import '../../css/h/h7jmoqb4s.css';
import '../../css/l/lhgbtcbov.css';
import '../../css/j/j8yh1x58g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q693w62tt"/><path class="h7jmoqb4s"/><path class="lhgbtcbov"/><path class="j8yh1x58g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pcn-military" /></template>

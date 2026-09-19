<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kbu_e79xt.css';
import '../../css/m/m8bh_vb-g.css';
import '../../css/o/oul2otxis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="kbu_e79xt"/><path class="m8bh_vb-g"/><path class="oul2otxis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:oncoming-fist-medium" /></template>

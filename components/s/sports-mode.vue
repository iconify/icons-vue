<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwvv-yb1g.css';
import '../../css/s/s7_2r_b_x.css';
import '../../css/k/k34urac1b.css';
import '../../css/o/ojzec6byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="uwvv-yb1g"/><path class="s7_2r_b_x"/><path class="k34urac1b"/><path class="ojzec6byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:sports-mode" /></template>

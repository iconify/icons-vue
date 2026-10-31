<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m5l09lw9e.css';
import '../../css/n/nd9377kmj.css';
import '../../css/k/kybbdjr2c.css';
import '../../css/f/fe1ja0b_n.css';
import '../../css/h/hpjrccjis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m5l09lw9e wm-k"/><path class="nd9377kmj wm-shine"/><path class="kybbdjr2c wm-shine"/><path class="fe1ja0b_n wm-shine"/><path class="hpjrccjis wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:mail" /></template>

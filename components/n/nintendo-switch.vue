<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/xuuig3bfw.css';
import '../../css/m/mjv0wacus.css';
import '../../css/q/qlniz9tvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="xuuig3bfw"/><path class="mjv0wacus"/><path class="qlniz9tvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:nintendo-switch" /></template>

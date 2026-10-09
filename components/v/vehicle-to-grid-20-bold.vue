<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxklois4m.css';
import '../../css/t/t_7rprl1m.css';
import '../../css/u/ufn12ktbs.css';
import '../../css/u/uale--bkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dxklois4m"/><path class="t_7rprl1m"/><path class="ufn12ktbs"/><path class="uale--bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vehicle-to-grid-20-bold" /></template>

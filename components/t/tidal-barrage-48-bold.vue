<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5ysxv9-t.css';
import '../../css/k/ktv_y0_2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w5ysxv9-t"/><path class="ktv_y0_2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tidal-barrage-48-bold" /></template>

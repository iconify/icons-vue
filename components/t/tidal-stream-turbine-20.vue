<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiv8dnhip.css';
import '../../css/v/v5b4nab0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qiv8dnhip"/><path class="v5b4nab0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tidal-stream-turbine-20" /></template>

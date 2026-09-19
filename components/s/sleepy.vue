<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzwd2419d.css';
import '../../css/m/m5myy5blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lzwd2419d"/><path class="m5myy5blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:sleepy" /></template>

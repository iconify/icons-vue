<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxcjxo_wu.css';
import '../../css/x/xtrfu-zjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dxcjxo_wu"/><path class="xtrfu-zjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:toggle-right-48-bold" /></template>

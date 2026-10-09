<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxcjxo_wu.css';
import '../../css/c/c_4ww1bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dxcjxo_wu"/><path class="c_4ww1bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:toggle-left-48-bold" /></template>

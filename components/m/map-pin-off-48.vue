<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xneu8q3zz.css';
import '../../css/n/n5wvztb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xneu8q3zz"/><path class="n5wvztb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:map-pin-off-48" /></template>

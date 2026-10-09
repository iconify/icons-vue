<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbfpednqz.css';
import '../../css/z/zl1nmrb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qbfpednqz"/><path class="zl1nmrb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rotor-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3in-zb7w.css';
import '../../css/j/jtlfsbcyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z3in-zb7w"/><path class="jtlfsbcyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-thermal-48-bold" /></template>

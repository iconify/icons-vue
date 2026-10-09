<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7-dvibjv.css';
import '../../css/c/c2_o5pxqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o7-dvibjv"/><path class="c2_o5pxqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wallet-48" /></template>

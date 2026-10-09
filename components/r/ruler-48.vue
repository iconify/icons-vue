<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fggx0lbvr.css';
import '../../css/q/q01m64b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fggx0lbvr"/><path class="q01m64b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ruler-48" /></template>

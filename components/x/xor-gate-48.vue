<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdb70jjls.css';
import '../../css/n/n-cuddbov.css';
import '../../css/k/koaj76bea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wdb70jjls"/><path class="n-cuddbov"/><path class="koaj76bea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:xor-gate-48" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fif1fofps.css';
import '../../css/k/kj_8dbkmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fif1fofps"/><path class="kj_8dbkmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monopole-pylon-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1ayl8bhm.css';
import '../../css/w/wf0j1sc4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s1ayl8bhm"/><path class="wf0j1sc4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-insulation-48" /></template>

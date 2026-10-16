<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxyna-beg.css';
import '../../css/g/gr-g1kq_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pxyna-beg"/><path class="gr-g1kq_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tide-low-48" /></template>

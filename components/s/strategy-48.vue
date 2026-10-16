<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cehi_ab5l.css';
import '../../css/l/lp3-t_bhn.css';
import '../../css/p/phjpdo02s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cehi_ab5l"/><path class="lp3-t_bhn"/><path class="phjpdo02s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:strategy-48" /></template>

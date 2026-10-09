<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz30y8b3r.css';
import '../../css/u/ucqd8s_7s.css';
import '../../css/k/kc5_9-b5b.css';
import '../../css/l/l3vqhjbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dz30y8b3r"/><path class="ucqd8s_7s"/><path class="kc5_9-b5b"/><path class="l3vqhjbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ventilation-20" /></template>

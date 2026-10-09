<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_dv-4xcr.css';
import '../../css/x/xb74i3b_v.css';
import '../../css/q/qh3-d7bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d_dv-4xcr"/><path class="xb74i3b_v"/><path class="qh3-d7bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:planning-consent-20" /></template>

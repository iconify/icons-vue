<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb3dwjb-x.css';
import '../../css/w/ws2z2pb6w.css';
import '../../css/o/o8u3-vbsf.css';
import '../../css/l/l3upj4-7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sb3dwjb-x"/><path class="ws2z2pb6w"/><path class="o8u3-vbsf"/><path class="l3upj4-7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:permafrost-20" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2p_4xcpi.css';
import '../../css/g/gj10flppe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x2p_4xcpi"/><path class="gj10flppe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tidal-barrage-20" /></template>

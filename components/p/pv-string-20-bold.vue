<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8ty_obto.css';
import '../../css/k/k5iv_0bgd.css';
import '../../css/q/q2a6e-bhn.css';
import '../../css/v/vw-knh15p.css';
import '../../css/e/e1y966bxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q8ty_obto"/><path class="k5iv_0bgd"/><path class="q2a6e-bhn"/><path class="vw-knh15p"/><path class="e1y966bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pv-string-20-bold" /></template>

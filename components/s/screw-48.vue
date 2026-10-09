<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnk74hkus.css';
import '../../css/k/kwnsnzbar.css';
import '../../css/k/k5ji0xe4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tnk74hkus"/><path class="kwnsnzbar"/><path class="k5ji0xe4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:screw-48" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pni5u1bji.css';
import '../../css/h/hv0sd2vvm.css';
import '../../css/w/w550r6lgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pni5u1bji"/><path class="hv0sd2vvm"/><path class="w550r6lgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mountain-river-48-bold" /></template>

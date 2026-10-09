<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzd46y33w.css';
import '../../css/t/t2f8pkdzv.css';
import '../../css/r/r7o-yybha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mzd46y33w"/><path class="t2f8pkdzv"/><path class="r7o-yybha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rov-20" /></template>

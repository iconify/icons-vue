<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiqnuhsan.css';
import '../../css/z/zzrqikhhv.css';
import '../../css/h/hb-shkb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qiqnuhsan"/><path class="zzrqikhhv"/><path class="hb-shkb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:synchronous-condenser-20" /></template>

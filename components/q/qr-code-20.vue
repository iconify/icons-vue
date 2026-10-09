<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka0hemtmx.css';
import '../../css/c/cm0047wom.css';
import '../../css/i/ij08oib1e.css';
import '../../css/o/opl2tbcms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ka0hemtmx"/><path class="cm0047wom"/><path class="ij08oib1e"/><path class="opl2tbcms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:qr-code-20" /></template>

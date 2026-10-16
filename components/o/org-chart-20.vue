<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k32gpe-6w.css';
import '../../css/u/uq2goxbcr.css';
import '../../css/c/csv0x4boa.css';
import '../../css/v/vny9clrdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k32gpe-6w"/><path class="uq2goxbcr"/><path class="csv0x4boa"/><path class="vny9clrdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:org-chart-20" /></template>

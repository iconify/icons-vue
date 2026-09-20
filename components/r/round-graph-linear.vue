<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gsb-xubkp.css';
import '../../css/z/zgimw8w5b.css';
import '../../css/a/a09g2ehcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gsb-xubkp"/><path class="zgimw8w5b"/><path class="a09g2ehcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-graph-linear" /></template>

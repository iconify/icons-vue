<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v0dnq2b7o.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/g/gradl1bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="v0dnq2b7o"/><circle class="h_tsn8bxt"/><circle class="gradl1bjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:menu-dots-linear" /></template>

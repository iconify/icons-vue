<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pxc0ebrta.css';
import '../../css/b/bl6ucdcay.css';
import '../../css/s/sqndjhubq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pxc0ebrta"/><path class="bl6ucdcay"/><path class="sqndjhubq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:telescope-linear" /></template>

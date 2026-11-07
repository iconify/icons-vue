<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gt-b8gb9l.css';
import '../../css/i/ige762y5f.css';
import '../../css/h/hl1uepbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gt-b8gb9l"/><path class="ige762y5f"/><path class="hl1uepbsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wind-broken" /></template>

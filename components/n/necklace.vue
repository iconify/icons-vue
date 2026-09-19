<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/oj79fp0oa.css';
import '../../css/f/fr4pg2b_d.css';
import '../../css/o/ojke_mb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oj79fp0oa"/><path class="fr4pg2b_d"/><path class="ojke_mb9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:necklace" /></template>

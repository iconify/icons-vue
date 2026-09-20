<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pckaxha-v.css';
import '../../css/i/ijwbgek4s.css';
import '../../css/y/y_s7vvbss.css';
import '../../css/w/w1fn0ab-e.css';
import '../../css/q/q-ve4mbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pckaxha-v"/><path class="ijwbgek4s"/><path class="y_s7vvbss"/><path class="w1fn0ab-e"/><path class="q-ve4mbnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:scanner-broken" /></template>

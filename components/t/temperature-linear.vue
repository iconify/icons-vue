<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/ror8fyj6a.css';
import '../../css/u/ul0rk9bgh.css';
import '../../css/w/w29ath28m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ror8fyj6a"/><path class="ul0rk9bgh"/><path class="w29ath28m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:temperature-linear" /></template>

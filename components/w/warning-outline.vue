<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlzy0nb1j.css';
import '../../css/n/n32zg0b1z.css';
import '../../css/u/ugcydkb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlzy0nb1j"/><circle class="n32zg0b1z"/><path class="ugcydkb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:warning-outline" /></template>

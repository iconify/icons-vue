<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/a3r6b-b4d.css';
import '../../css/s/s9qxbdczi.css';
import '../../css/u/urvibib1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="a3r6b-b4d"/><path class="s9qxbdczi"/><path class="urvibib1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-angular-broken" /></template>

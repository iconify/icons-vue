<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g626xxb-k.css';
import '../../css/q/qlcb99brl.css';
import '../../css/e/e6bz15b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g626xxb-k"/><path class="qlcb99brl"/><path class="e6bz15b5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-top-left-broken" /></template>

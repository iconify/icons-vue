<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/du-5mnkon.css';
import '../../css/o/o17q8nbkk.css';
import '../../css/e/eawrvo-zk.css';
import '../../css/a/a9qq5obmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="du-5mnkon"/><path class="o17q8nbkk"/><path class="eawrvo-zk"/><path class="a9qq5obmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-map-point-line-duotone" /></template>

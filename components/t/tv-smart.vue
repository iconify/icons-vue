<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u1vhlt4_a.css';
import '../../css/g/g3loe6yfe.css';
import '../../css/f/felm6jbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u1vhlt4_a"/><path class="g3loe6yfe"/><path class="felm6jbve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tv-smart" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e2irt0b7x.css';
import '../../css/i/ihw3qzrvl.css';
import '../../css/p/pkn-bebts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e2irt0b7x"/><path class="ihw3qzrvl"/><path class="pkn-bebts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tsunami" /></template>

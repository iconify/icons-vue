<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utf77lbef.css';
import '../../css/u/ul24yyxty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="utf77lbef"/><path class="ul24yyxty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:price-spike-48" /></template>

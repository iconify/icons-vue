<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr-eedcjf.css';
import '../../css/u/ua1y3_b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tr-eedcjf"/><path class="ua1y3_b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:podium-48-bold" /></template>

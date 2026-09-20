<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwzs1uccg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kwzs1uccg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-token-count" /></template>

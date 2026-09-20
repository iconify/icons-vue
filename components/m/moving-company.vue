<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib88ljbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ib88ljbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:moving-company" /></template>

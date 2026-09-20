<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlf6_vbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="mlf6_vbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:playground" /></template>

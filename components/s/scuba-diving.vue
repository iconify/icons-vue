<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1fcab9xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="m1fcab9xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:scuba-diving" /></template>

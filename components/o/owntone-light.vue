<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgmydkb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qgmydkb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:owntone-light" /></template>

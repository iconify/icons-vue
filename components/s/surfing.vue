<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nopl6cb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="nopl6cb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:surfing" /></template>

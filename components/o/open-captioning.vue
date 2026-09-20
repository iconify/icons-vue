<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwjl9f13w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="rwjl9f13w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:open-captioning" /></template>

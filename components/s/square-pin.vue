<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6r8g0bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="p6r8g0bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:square-pin" /></template>

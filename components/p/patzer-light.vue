<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmoj0pv_m.css';
import '../../css/m/ml0m__bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nmoj0pv_m"/><path class="ml0m__bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:patzer-light" /></template>

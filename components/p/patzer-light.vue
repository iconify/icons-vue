<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmoj0pv_m.css';
import '../../css/i/iuvjulbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nmoj0pv_m"/><path class="iuvjulbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:patzer-light" /></template>

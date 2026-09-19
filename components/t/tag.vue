<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxy_h0r5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="rxy_h0r5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:tag" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saf42g1dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="saf42g1dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plc" /></template>

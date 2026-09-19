<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbv4wpb-c.css';
import '../../css/c/csr9vodhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="zbv4wpb-c"/><circle class="csr9vodhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-point-on-surface" /></template>

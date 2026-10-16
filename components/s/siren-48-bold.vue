<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guu8cvajv.css';
import '../../css/d/dfl7556qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="guu8cvajv"/><path class="dfl7556qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:siren-48-bold" /></template>

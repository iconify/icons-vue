<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3gb8_t8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r3gb8_t8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-excel-2018-light" /></template>

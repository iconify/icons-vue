<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh4_mkb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="sh4_mkb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:plus-circle-o" /></template>

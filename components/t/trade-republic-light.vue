<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr_hn414m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wr_hn414m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trade-republic-light" /></template>

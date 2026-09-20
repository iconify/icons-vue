<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdhcrkb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bdhcrkb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextbeats-light" /></template>

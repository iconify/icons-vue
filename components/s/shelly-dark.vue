<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0gkymnnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y0gkymnnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shelly-dark" /></template>

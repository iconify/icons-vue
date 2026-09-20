<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ota9e_b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ota9e_b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pulse-light" /></template>

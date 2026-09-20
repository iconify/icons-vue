<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6b09o61e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w6b09o61e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ownfoil" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lta_4qb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lta_4qb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-epinio-light" /></template>

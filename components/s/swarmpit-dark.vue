<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc6h766dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lc6h766dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:swarmpit-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqdnidbra.css';
import '../../css/z/zkw9hjbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iqdnidbra"/><path class="zkw9hjbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:threadfin-dark" /></template>

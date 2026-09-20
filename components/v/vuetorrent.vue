<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u54g6q6wc.css';
import '../../css/m/m-64o3ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u54g6q6wc"/><path class="m-64o3ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vuetorrent" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa1e5mbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sa1e5mbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openwrt-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw99vsbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gw99vsbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-rio-light" /></template>

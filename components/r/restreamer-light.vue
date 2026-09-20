<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nseg2ysar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nseg2ysar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:restreamer-light" /></template>

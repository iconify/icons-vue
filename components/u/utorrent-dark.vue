<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhqab3bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qhqab3bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:utorrent-dark" /></template>

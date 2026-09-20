<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa8o-xbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wa8o-xbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zerobyte-dark" /></template>

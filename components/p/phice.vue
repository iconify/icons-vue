<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw3y1unhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iw3y1unhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phice" /></template>

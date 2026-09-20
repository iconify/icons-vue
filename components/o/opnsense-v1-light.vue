<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4p2bsbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u4p2bsbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opnsense-v1-light" /></template>

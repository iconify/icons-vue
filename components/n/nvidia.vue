<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip2z-kb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ip2z-kb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nvidia" /></template>

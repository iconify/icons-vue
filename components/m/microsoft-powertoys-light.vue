<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dicgffbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dicgffbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-powertoys-light" /></template>

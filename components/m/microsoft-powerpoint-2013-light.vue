<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9vw_m5_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y9vw_m5_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-powerpoint-2013-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_mv9ccml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_mv9ccml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:slskd-light" /></template>

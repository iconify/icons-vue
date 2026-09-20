<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrm_zs23m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mrm_zs23m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:travstats-dark" /></template>

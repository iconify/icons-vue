<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcwrfsx8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dcwrfsx8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:orb" /></template>

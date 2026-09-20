<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwy927bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rwy927bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailjet-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5sc99b2m.css';
import '../../css/m/m3i3t-iqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5sc99b2m"/><path class="m3i3t-iqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spooty-dark" /></template>

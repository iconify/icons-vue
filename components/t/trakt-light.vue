<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no2_z4syg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="no2_z4syg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trakt-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5s8215rm.css';
import '../../css/m/mkgj1odis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i5s8215rm"/><path class="mkgj1odis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reclaimerr-dark" /></template>

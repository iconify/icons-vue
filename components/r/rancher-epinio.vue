<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0oiyblvd.css';
import '../../css/n/nxr9mlzqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i0oiyblvd"/><path class="nxr9mlzqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-epinio" /></template>

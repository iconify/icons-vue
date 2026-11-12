<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilcrn3bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ilcrn3bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-fleet-dark" /></template>

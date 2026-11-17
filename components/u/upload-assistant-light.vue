<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2x2dyavi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l2x2dyavi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:upload-assistant-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-dskr72e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i-dskr72e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:readarr-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdr_4acws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hdr_4acws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pleroma" /></template>

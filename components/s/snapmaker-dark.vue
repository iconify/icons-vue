<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcm2r0bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dcm2r0bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:snapmaker-dark" /></template>

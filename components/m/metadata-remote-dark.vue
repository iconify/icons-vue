<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmu_k5bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vmu_k5bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:metadata-remote-dark" /></template>

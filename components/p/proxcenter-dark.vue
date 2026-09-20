<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od-1d7bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="od-1d7bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proxcenter-dark" /></template>

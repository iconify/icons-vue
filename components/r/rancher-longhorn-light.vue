<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvqudbbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cvqudbbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-longhorn-light" /></template>

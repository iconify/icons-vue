<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usmd_2bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="usmd_2bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openmediavault-dark" /></template>

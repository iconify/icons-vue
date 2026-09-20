<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnogg_brt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rnogg_brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openmediavault-light" /></template>

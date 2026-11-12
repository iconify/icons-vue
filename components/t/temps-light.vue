<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6f0j9bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x6f0j9bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:temps-light" /></template>

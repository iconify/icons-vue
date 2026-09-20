<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icyvf5brz.css';
import '../../css/b/bfueulvzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="icyvf5brz"/><path class="bfueulvzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:post-content" /></template>

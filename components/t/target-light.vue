<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvz_3cbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kvz_3cbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:target-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7rzl_-gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x7rzl_-gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:seagate-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e38ldbc6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e38ldbc6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shako-light" /></template>

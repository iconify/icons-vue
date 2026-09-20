<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggnt94bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ggnt94bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proxmenux-light" /></template>

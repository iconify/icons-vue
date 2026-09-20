<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov7c-h-ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ov7c-h-ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proxcenter-light" /></template>

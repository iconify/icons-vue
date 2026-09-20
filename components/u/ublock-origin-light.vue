<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxuj48blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oxuj48blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ublock-origin-light" /></template>

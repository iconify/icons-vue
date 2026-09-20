<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t99fmgbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t99fmgbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-outlook-2013-light" /></template>

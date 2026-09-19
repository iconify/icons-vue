<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm_cfgbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="nm_cfgbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:replay-5" /></template>

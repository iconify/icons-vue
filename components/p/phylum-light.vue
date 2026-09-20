<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgr2qrbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xgr2qrbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phylum-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlho3t-wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wlho3t-wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:tiktok" /></template>

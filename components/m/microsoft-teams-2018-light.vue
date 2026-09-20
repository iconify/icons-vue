<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq1_-xbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lq1_-xbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-teams-2018-light" /></template>

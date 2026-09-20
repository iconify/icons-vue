<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kob1615rl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kob1615rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openlist-light" /></template>

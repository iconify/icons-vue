<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqo5wlb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bqo5wlb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:octobot-light" /></template>

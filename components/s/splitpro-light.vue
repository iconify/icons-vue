<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g58_hc9td.css';
import '../../css/w/wh_63k2aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g58_hc9td"/><path class="wh_63k2aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:splitpro-light" /></template>

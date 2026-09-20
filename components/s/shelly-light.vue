<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv13l7o3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vv13l7o3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shelly-light" /></template>

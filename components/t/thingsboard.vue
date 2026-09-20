<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfan_xeus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xfan_xeus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:thingsboard" /></template>

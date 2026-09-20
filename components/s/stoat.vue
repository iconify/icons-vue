<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycbseobgb.css';
import '../../css/d/dbcsx4b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ycbseobgb"/><path class="dbcsx4b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stoat" /></template>

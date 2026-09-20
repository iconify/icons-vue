<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvmyrwbcs.css';
import '../../css/p/pvt38-bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dvmyrwbcs"/><path class="pvt38-bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vue-js" /></template>

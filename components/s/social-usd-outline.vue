<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv4biccwc.css';
import '../../css/o/oa67cbk0z.css';
import '../../css/v/v-i1hztch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yv4biccwc"/><path class="oa67cbk0z"/><path class="v-i1hztch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-usd-outline" /></template>

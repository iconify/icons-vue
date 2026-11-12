<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrl71abcz.css';
import '../../css/i/ilzd2fb8z.css';
import '../../css/a/afvuxlb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGxR7jmcOj" x1="93.9" x2="163.3" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="xrl71abcz"/><stop offset="1" class="ilzd2fb8z"/></linearGradient><path fill="url(#SVGxR7jmcOj)" class="afvuxlb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mantrae" /></template>

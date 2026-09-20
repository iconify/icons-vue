<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wionk-b8u.css';
import '../../css/n/n_arg_b-v.css';
import '../../css/r/r2rl9cbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGcJptGk5B" x1="0" x2="512" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="wionk-b8u"/><stop offset="1" class="n_arg_b-v"/></linearGradient><path fill="url(#SVGcJptGk5B)" class="r2rl9cbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wastebin" /></template>

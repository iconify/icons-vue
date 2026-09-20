<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy7st-bkc.css';
import '../../css/y/yf-f_bcue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dy7st-bkc"/><path class="yf-f_bcue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tailscale" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlgv7ybbq.css';
import '../../css/b/bpn70zs4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wlgv7ybbq"/><path class="bpn70zs4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rackula" /></template>

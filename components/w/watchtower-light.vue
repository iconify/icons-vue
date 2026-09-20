<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj4sx_wkb.css';
import '../../css/i/ipyyj6ggt.css';
import '../../css/s/sun_m7tdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mj4sx_wkb"/><path class="ipyyj6ggt"/><path class="sun_m7tdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:watchtower-light" /></template>

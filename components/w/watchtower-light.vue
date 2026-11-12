<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj4sx_wkb.css';
import '../../css/v/vp08acc_f.css';
import '../../css/k/kpqed-bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mj4sx_wkb"/><path class="vp08acc_f"/><path class="kpqed-bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:watchtower-light" /></template>

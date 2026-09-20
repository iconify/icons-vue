<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpazd_-xr.css';
import '../../css/s/sn42oqj_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bpazd_-xr"/><path class="sn42oqj_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:onetime-secret" /></template>

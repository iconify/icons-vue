<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzr2p1b8f.css';
import '../../css/a/aen1w6b6m.css';
import '../../css/v/vi3rgwb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xzr2p1b8f"/><path class="aen1w6b6m"/><path class="vi3rgwb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:whitetouchtonephone" /></template>

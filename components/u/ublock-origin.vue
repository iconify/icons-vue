<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn_etb2ed.css';
import '../../css/a/aoms7-zgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xn_etb2ed"/><path class="aoms7-zgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ublock-origin" /></template>

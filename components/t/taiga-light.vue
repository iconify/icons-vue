<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxjnv6btj.css';
import '../../css/o/o78-gg1um.css';
import '../../css/m/mam2srhpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pxjnv6btj"/><path class="o78-gg1um"/><path class="mam2srhpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:taiga-light" /></template>

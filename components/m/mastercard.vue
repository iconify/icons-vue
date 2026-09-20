<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzm141dva.css';
import '../../css/d/d-spf-bpy.css';
import '../../css/n/ndr05hb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zzm141dva"/><path class="d-spf-bpy"/><path class="ndr05hb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mastercard" /></template>

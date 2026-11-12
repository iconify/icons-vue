<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpazd_-xr.css';
import '../../css/t/tnu5vf6mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bpazd_-xr"/><path class="tnu5vf6mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:onetime-secret" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iycln-b8i.css';
import '../../css/v/vmwphib4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="iycln-b8i"/><path class="vmwphib4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:voltaserve" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay8vxacgb.css';
import '../../css/a/ap5bgib7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG8o2CqbeA" x1="48.154" x2="115.519" y1="575.296" y2="408.562" gradientTransform="matrix(2.8479 0 0 -2.8498 18.77 1647.39)" gradientUnits="userSpaceOnUse"><stop offset=".01"/><stop offset="1" class="ay8vxacgb"/></linearGradient><path fill="url(#SVG8o2CqbeA)" class="ap5bgib7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vaultls-dark" /></template>

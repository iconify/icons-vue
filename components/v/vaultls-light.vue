<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/t/tb9i-5hiz.css';
import '../../css/a/ap5bgib7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGTYfXsZSk" x1="48.154" x2="115.519" y1="575.296" y2="408.562" gradientTransform="matrix(2.8479 0 0 -2.8498 18.77 1647.39)" gradientUnits="userSpaceOnUse"><stop offset=".01" class="vc--wpv5i"/><stop offset="1" class="tb9i-5hiz"/></linearGradient><path fill="url(#SVGTYfXsZSk)" class="ap5bgib7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vaultls-light" /></template>

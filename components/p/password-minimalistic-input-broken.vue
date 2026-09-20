<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/om4lnzbpu.css';
import '../../css/b/bpkt4gbdh.css';
import '../../css/s/sp15d0bxe.css';
import '../../css/k/km0rz_boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="om4lnzbpu"/><path class="bpkt4gbdh"/><path class="sp15d0bxe"/><path class="km0rz_boi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:password-minimalistic-input-broken" /></template>

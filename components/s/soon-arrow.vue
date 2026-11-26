<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iakx74-2k.css';
import '../../css/b/bgmlavupy.css';
import '../../css/g/gdlj141wo.css';
import '../../css/n/nt1nkohqh.css';
import '../../css/c/cb2bdtlge.css';
import '../../css/u/un8e6hbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><radialGradient id="SVG2Yhqttuf" cx="79" cy="62.2" r="120" gradientUnits="userSpaceOnUse"><stop offset="0" class="iakx74-2k"/><stop offset=".85" class="bgmlavupy"/><stop offset="1" class="bgmlavupy"/></radialGradient></defs><path class="gdlj141wo"/><path fill="url(#SVG2Yhqttuf)" transform="matrix(2.8 0 0 2.8 -28.016 -35.136)" class="nt1nkohqh"/><path class="cb2bdtlge"/><path class="un8e6hbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="xero-emoji:soon-arrow" /></template>
